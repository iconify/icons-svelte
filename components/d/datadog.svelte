<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7nqbbw5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="j7nqbbw5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:datadog" {...props}></Icon>

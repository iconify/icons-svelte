<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6c1haceh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="u6c1haceh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:jquery" {...props}></Icon>

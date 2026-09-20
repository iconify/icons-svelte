<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5ty9xb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o5ty9xb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:rocket-16" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woi1m74fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="woi1m74fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:eye-closed-16" {...props}></Icon>

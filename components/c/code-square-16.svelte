<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecc2mpxmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ecc2mpxmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:code-square-16" {...props}></Icon>

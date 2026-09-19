<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgi2k-5vf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rgi2k-5vf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:deployment-unit-technical-installation" {...props}></Icon>

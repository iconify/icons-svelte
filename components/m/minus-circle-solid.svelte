<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq4ay1j3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uq4ay1j3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:minus-circle-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu28wcqsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cu28wcqsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:copy-plus" {...props}></Icon>

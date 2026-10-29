<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe6o2fhjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oe6o2fhjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-search-corner" {...props}></Icon>

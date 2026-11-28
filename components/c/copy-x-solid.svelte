<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuu_75j-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xuu_75j-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:copy-x-solid" {...props}></Icon>

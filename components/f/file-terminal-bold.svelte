<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd-wbsxqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zd-wbsxqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-terminal-bold" {...props}></Icon>

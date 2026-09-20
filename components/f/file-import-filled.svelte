<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxzbmtabh.css';
import '../../css/y/y663-_bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxzbmtabh"/><path class="y663-_bpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-import-filled" {...props}></Icon>

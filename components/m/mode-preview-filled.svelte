<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbm9vfskf.css';
import '../../css/t/tiuq2lb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbm9vfskf"/><path class="tiuq2lb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mode-preview-filled" {...props}></Icon>

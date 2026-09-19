<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h76a9ql5h.css';
import '../../css/i/i5o3gv_dc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer h76a9ql5h"/><path class="duoicon-secondary-layer i5o3gv_dc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:computer-camera" {...props}></Icon>

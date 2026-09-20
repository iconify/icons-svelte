<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqm469b_j.css';
import '../../css/m/mjpn8j_wb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqm469b_j"/><path class="mjpn8j_wb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-wechat" {...props}></Icon>

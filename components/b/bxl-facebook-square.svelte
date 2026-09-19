<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qeq6kv7wx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qeq6kv7wx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-facebook-square" {...props}></Icon>

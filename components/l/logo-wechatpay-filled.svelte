<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrtxqzr9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrtxqzr9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-wechatpay-filled" {...props}></Icon>

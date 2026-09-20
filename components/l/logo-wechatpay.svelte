<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayvpk_rku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayvpk_rku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-wechatpay" {...props}></Icon>

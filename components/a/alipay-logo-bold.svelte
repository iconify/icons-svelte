<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz71yshvb.css';
import '../../css/k/k9--tbbhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hz71yshvb"/><path class="k9--tbbhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:alipay-logo-bold" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nexp954-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nexp954-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:alipay-line" {...props}></Icon>

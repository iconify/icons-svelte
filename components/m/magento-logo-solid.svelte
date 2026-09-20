<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce_5lo_lk.css';
import '../../css/o/opmfvvg-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ce_5lo_lk"/><path class="opmfvvg-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:magento-logo-solid" {...props}></Icon>

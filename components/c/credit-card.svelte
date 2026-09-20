<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lerk_xbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lerk_xbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:credit-card" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usd_jbcxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usd_jbcxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:handbag-round" {...props}></Icon>

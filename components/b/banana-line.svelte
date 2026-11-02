<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpcnftbyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpcnftbyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:banana-line" {...props}></Icon>

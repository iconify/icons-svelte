<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmc2pd60s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmc2pd60s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:invoice-round" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq1j11bcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xq1j11bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:piggy-bank-round" {...props}></Icon>

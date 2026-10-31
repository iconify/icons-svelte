<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbf-hnbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbf-hnbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-area-fill-round" {...props}></Icon>

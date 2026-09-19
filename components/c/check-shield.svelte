<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbp_6dbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbp_6dbny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:check-shield" {...props}></Icon>

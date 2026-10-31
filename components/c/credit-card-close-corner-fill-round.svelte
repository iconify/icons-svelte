<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl96inlcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fl96inlcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:credit-card-close-corner-fill-round" {...props}></Icon>

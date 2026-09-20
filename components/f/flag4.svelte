<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie766ibcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie766ibcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:flag4" {...props}></Icon>

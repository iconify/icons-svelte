<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quh_6hblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="quh_6hblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:egg-fill-round" {...props}></Icon>

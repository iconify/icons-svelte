<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zen96loip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zen96loip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:10-play" {...props}></Icon>

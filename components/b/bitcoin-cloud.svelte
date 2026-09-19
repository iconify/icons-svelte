<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzopyybng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzopyybng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bitcoin-cloud" {...props}></Icon>

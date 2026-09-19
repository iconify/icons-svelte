<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asfzddcic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asfzddcic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:acceleration" {...props}></Icon>

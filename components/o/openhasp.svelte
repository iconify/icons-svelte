<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1m3qyznc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1m3qyznc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:openhasp" {...props}></Icon>

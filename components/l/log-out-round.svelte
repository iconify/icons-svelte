<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3zsfc7ye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3zsfc7ye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:log-out-round" {...props}></Icon>

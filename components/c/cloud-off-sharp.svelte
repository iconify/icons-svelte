<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3u9yv-3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3u9yv-3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cloud-off-sharp" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb00t0bjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wb00t0bjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-up-small-fill-round" {...props}></Icon>

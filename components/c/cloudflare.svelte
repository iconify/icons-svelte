<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo3h003kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":31,"height":24};
const content = `<path class="eo3h003kd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:cloudflare" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iku0ku7vq.css';
import '../../css/t/t1somzbtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iku0ku7vq"/><path class="t1somzbtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dry-cask-20" {...props}></Icon>

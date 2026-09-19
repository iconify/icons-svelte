<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kydmqcc5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kydmqcc5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:fullscreen-alt" {...props}></Icon>

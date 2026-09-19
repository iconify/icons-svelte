<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubbkpfkka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ubbkpfkka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:playlist-audio" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n339tvehl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n339tvehl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pencil-ruler-line" {...props}></Icon>

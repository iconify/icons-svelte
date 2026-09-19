<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsa1ivb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsa1ivb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:rocket" {...props}></Icon>

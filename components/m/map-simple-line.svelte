<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8ac9puxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8ac9puxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:map-simple-line" {...props}></Icon>

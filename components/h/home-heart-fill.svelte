<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6e9kemdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6e9kemdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:home-heart-fill" {...props}></Icon>

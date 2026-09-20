<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt34pac0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pt34pac0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-paint" {...props}></Icon>

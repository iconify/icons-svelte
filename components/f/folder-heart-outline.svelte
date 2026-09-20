<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_k6yvtja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_k6yvtja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-heart-outline" {...props}></Icon>

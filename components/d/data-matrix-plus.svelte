<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk6ek7b-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk6ek7b-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:data-matrix-plus" {...props}></Icon>

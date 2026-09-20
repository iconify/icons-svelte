<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyuns3bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyuns3bxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:card-off" {...props}></Icon>

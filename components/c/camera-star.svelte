<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9rbi7bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9rbi7bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:camera-star" {...props}></Icon>

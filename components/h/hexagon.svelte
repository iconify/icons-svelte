<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6g5b-1bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6g5b-1bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:hexagon" {...props}></Icon>

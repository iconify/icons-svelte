<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn68y7huu.css';
import '../../css/h/hwymrt-6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mn68y7huu"/><path class="hwymrt-6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:podcast-bold" {...props}></Icon>

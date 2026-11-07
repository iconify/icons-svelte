<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq8bxxi9p.css';
import '../../css/i/iads9dnva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zq8bxxi9p"/><path class="iads9dnva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:crown-star-bold-duotone" {...props}></Icon>

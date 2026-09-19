<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr1uwtbsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="tr1uwtbsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:low-vision" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wky32j_ur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wky32j_ur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:frown" {...props}></Icon>

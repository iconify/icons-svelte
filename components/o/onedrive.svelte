<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy2q4fbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uy2q4fbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:onedrive" {...props}></Icon>

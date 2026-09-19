<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz5t1_nzh.css';
import '../../css/e/evz6bnbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fz5t1_nzh"/><path class="evz6bnbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:creative-commons-share" {...props}></Icon>

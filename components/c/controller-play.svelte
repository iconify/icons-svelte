<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa_egxbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sa_egxbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:controller-play" {...props}></Icon>

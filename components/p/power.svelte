<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruf9kkree.css';
import '../../css/n/n0nc54wee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ruf9kkree"/><path class="n0nc54wee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:power" {...props}></Icon>

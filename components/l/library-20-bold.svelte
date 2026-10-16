<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv842m9yr.css';
import '../../css/f/fl7bzqbcv.css';
import '../../css/n/nhkqt2bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yv842m9yr"/><path class="fl7bzqbcv"/><path class="nhkqt2bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:library-20-bold" {...props}></Icon>

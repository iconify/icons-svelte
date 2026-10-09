<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnjkukbmw.css';
import '../../css/o/ozisc9lak.css';
import '../../css/w/waeycxb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rnjkukbmw"/><path class="ozisc9lak"/><path class="waeycxb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-offset-20" {...props}></Icon>

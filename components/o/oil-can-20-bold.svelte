<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy5740rad.css';
import '../../css/f/f34cgmbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wy5740rad"/><path class="f34cgmbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:oil-can-20-bold" {...props}></Icon>

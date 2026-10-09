<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_wx6iigs.css';
import '../../css/h/hh85jcb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n_wx6iigs"/><path class="hh85jcb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:city-skyline-20" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7byejq-o.css';
import '../../css/c/c3mb_pbac.css';
import '../../css/p/poj_abb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s7byejq-o"/><path class="c3mb_pbac"/><path class="poj_abb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:laser-level-20-bold" {...props}></Icon>

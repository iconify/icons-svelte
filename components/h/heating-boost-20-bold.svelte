<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omf76gbof.css';
import '../../css/f/f40uyxeum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="omf76gbof"/><path class="f40uyxeum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heating-boost-20-bold" {...props}></Icon>

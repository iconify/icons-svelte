<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmx-vlbrm.css';
import '../../css/j/jjyg4db0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pmx-vlbrm"/><path class="jjyg4db0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cargo-ship-48-bold" {...props}></Icon>

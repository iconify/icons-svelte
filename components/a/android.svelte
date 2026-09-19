<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj_wpibuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uj_wpibuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:android" {...props}></Icon>

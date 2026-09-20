<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_8dvglkn.css';
import '../../css/k/kwzja8bzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t_8dvglkn"/><path class="kwzja8bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-pipe" {...props}></Icon>

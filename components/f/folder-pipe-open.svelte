<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urkx-c35c.css';
import '../../css/k/kwzja8bzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="urkx-c35c"/><path class="kwzja8bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-pipe-open" {...props}></Icon>

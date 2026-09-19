<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecm9edcrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":392};
const content = `<path class="ecm9edcrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:favorite-outline" {...props}></Icon>

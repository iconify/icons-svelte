<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/friknfboq.css';
import '../../css/e/etv5vpb9k.css';
import '../../css/p/py1903b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="friknfboq"/><path class="etv5vpb9k"/><path class="py1903b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:export-limit-48" {...props}></Icon>

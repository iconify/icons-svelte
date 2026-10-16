<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikhyofbzz.css';
import '../../css/a/ay4i28ssf.css';
import '../../css/a/a6rc3ubbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ikhyofbzz"/><path class="ay4i28ssf"/><path class="a6rc3ubbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:agv-48-bold" {...props}></Icon>

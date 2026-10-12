<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t85dv3bhf.css';
import '../../css/h/hvlek604j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t85dv3bhf"/><path class="hvlek604j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:playlist-48-bold" {...props}></Icon>

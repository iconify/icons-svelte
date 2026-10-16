<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moyoz5fkv.css';
import '../../css/h/hlnkiidlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="moyoz5fkv"/><path class="hlnkiidlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:disc-48-bold" {...props}></Icon>

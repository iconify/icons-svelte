<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1mxhxbto.css';
import '../../css/y/yx1n2abfm.css';
import '../../css/h/h3f5vhb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p1mxhxbto"/><path class="yx1n2abfm"/><path class="h3f5vhb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hex-bolt-48-bold" {...props}></Icon>

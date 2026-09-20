<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/g/gz7pzxb9g.css';
import '../../css/w/w56pzz2bw.css';
import '../../css/j/jf5hngtdr.css';
import '../../css/s/s4aoiyb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><circle class="gz7pzxb9g"/><circle class="w56pzz2bw"/><circle class="jf5hngtdr"/><circle class="s4aoiyb6e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:grid-circles" {...props}></Icon>

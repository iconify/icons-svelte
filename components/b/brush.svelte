<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/f/f7r0l4_pc.css';
import '../../css/n/nj0w8c_ky.css';
import '../../css/n/nrx5hqbhr.css';
import '../../css/z/zsncxcx3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="f7r0l4_pc"/><path class="nj0w8c_ky"/><path class="nrx5hqbhr"/><path class="zsncxcx3d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:brush" {...props}></Icon>

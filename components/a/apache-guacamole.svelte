<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iycln-b8i.css';
import '../../css/u/ubauqy9wp.css';
import '../../css/c/cudjf8a_r.css';
import '../../css/z/zdzon5lta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="iycln-b8i"/><path class="ubauqy9wp"/><path class="cudjf8a_r"/><path class="zdzon5lta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apache-guacamole" {...props}></Icon>

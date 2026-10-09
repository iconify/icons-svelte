<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a23qezmoi.css';
import '../../css/h/hokkqjb4r.css';
import '../../css/d/dy4drqbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a23qezmoi"/><path class="hokkqjb4r"/><path class="dy4drqbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-station-48" {...props}></Icon>

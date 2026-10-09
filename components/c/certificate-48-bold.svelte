<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shndm-bvf.css';
import '../../css/d/d7fixtb7r.css';
import '../../css/l/lghqnqgnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="shndm-bvf"/><path class="d7fixtb7r"/><path class="lghqnqgnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:certificate-48-bold" {...props}></Icon>

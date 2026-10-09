<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ona24jwrs.css';
import '../../css/x/x1xwve8uf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ona24jwrs"/><path class="x1xwve8uf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cast-48-bold" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iri4s80tq.css';
import '../../css/j/jfedwfb_m.css';
import '../../css/l/lg562ex1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iri4s80tq"/><path class="jfedwfb_m"/><path class="lg562ex1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:org-unit" {...props}></Icon>

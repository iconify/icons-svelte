<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu98hpkgc.css';
import '../../css/u/uu29n6b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mu98hpkgc"/><path class="uu29n6b9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flowchart-48" {...props}></Icon>

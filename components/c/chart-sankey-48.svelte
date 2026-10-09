<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvtyb5b6l.css';
import '../../css/a/a_35o2j3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hvtyb5b6l"/><path class="a_35o2j3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-sankey-48" {...props}></Icon>

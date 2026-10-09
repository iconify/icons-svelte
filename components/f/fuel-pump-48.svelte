<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a23qezmoi.css';
import '../../css/u/u6et4xbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a23qezmoi"/><path class="u6et4xbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fuel-pump-48" {...props}></Icon>

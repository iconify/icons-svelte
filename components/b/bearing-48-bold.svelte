<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_6rndbde.css';
import '../../css/t/tem3d3bqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e_6rndbde"/><path class="tem3d3bqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bearing-48-bold" {...props}></Icon>

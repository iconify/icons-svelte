<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p860fxb3j.css';
import '../../css/i/igyv2ne6w.css';
import '../../css/o/o3ufdkm0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p860fxb3j"/><path class="igyv2ne6w"/><path class="o3ufdkm0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grid-flexibility-48" {...props}></Icon>

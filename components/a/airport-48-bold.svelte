<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa81hmtbv.css';
import '../../css/i/ik6s6dbfj.css';
import '../../css/n/n3iczmbsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aa81hmtbv"/><path class="ik6s6dbfj"/><path class="n3iczmbsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:airport-48-bold" {...props}></Icon>

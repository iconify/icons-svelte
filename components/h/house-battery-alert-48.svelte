<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajch12nad.css';
import '../../css/p/pi81u0bva.css';
import '../../css/x/x_6yldbeu.css';
import '../../css/i/ikpbwe38b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ajch12nad"/><path class="pi81u0bva"/><path class="x_6yldbeu"/><path class="ikpbwe38b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-battery-alert-48" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hac57wbhi.css';
import '../../css/k/knpp2accw.css';
import '../../css/k/kis5lmh2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hac57wbhi"/><path class="knpp2accw"/><path class="kis5lmh2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:globe-48" {...props}></Icon>

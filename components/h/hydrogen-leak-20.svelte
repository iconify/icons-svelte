<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi5uaactm.css';
import '../../css/r/rnzp9jboq.css';
import '../../css/v/vayq6bcaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hi5uaactm"/><path class="rnzp9jboq"/><path class="vayq6bcaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-leak-20" {...props}></Icon>

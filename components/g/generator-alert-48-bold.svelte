<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/koz4nrgjs.css';
import '../../css/s/st5lvs5dl.css';
import '../../css/y/ygtv74bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="koz4nrgjs"/><path class="st5lvs5dl"/><path class="ygtv74bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:generator-alert-48-bold" {...props}></Icon>

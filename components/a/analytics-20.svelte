<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k859r6bpa.css';
import '../../css/g/gvso01jpw.css';
import '../../css/k/kezlhjxnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k859r6bpa"/><path class="gvso01jpw"/><path class="kezlhjxnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:analytics-20" {...props}></Icon>

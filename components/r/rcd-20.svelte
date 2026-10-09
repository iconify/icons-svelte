<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw4_rr5le.css';
import '../../css/a/ahqrd-o5z.css';
import '../../css/n/npeb0bbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hw4_rr5le"/><path class="ahqrd-o5z"/><path class="npeb0bbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rcd-20" {...props}></Icon>

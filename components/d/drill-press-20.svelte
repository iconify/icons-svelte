<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzaxycb1h.css';
import '../../css/w/wcn0uyb2b.css';
import '../../css/k/kl3kspb4p.css';
import '../../css/h/hu2xs9w1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gzaxycb1h"/><path class="wcn0uyb2b"/><path class="kl3kspb4p"/><path class="hu2xs9w1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:drill-press-20" {...props}></Icon>

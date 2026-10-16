<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc_5blf9f.css';
import '../../css/g/gl1l9lb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lc_5blf9f"/><path class="gl1l9lb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:image-off-48" {...props}></Icon>

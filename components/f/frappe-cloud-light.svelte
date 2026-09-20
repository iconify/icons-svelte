<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mehs67sax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mehs67sax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-cloud-light" {...props}></Icon>

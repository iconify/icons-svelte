<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-y9qh32h.css';
import '../../css/z/zcvqqxblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g-y9qh32h"/><path class="zcvqqxblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:glacier-48" {...props}></Icon>

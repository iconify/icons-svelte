<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjg59kbok.css';
import '../../css/k/kdlzsghls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kjg59kbok"/><path class="kdlzsghls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:oauth2-proxy-light" {...props}></Icon>

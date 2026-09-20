<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bim1nbclp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bim1nbclp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:penn-state-nittany-lions-dark" {...props}></Icon>

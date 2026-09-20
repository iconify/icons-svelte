<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smdiurlld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="smdiurlld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cypht-dark" {...props}></Icon>

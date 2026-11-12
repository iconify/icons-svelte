<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/didt0l-fl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="didt0l-fl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-web-services-light" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf020ifmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yf020ifmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docuseal" {...props}></Icon>

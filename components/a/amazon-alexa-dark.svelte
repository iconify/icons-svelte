<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do-ojo0gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="do-ojo0gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-alexa-dark" {...props}></Icon>

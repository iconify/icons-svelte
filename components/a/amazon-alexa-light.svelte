<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fek5v6baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fek5v6baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-alexa-light" {...props}></Icon>

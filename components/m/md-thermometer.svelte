<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhz84bc7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hhz84bc7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-thermometer" {...props}></Icon>

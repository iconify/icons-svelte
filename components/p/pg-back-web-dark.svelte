<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe2kmybrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xe2kmybrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pg-back-web-dark" {...props}></Icon>

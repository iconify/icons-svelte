<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_jd-0b7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g_jd-0b7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adobe-photoshop-dark" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7g_vdc9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v7g_vdc9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pollaris-dark" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an_myyb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="an_myyb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netlify-dark" {...props}></Icon>

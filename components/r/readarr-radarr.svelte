<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-wkamaxf.css';
import '../../css/d/dmusveb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a-wkamaxf"/><path class="dmusveb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:readarr-radarr" {...props}></Icon>

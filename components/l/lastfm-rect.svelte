<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9pc-2vni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="y9pc-2vni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:lastfm-rect" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-wkamaxf.css';
import '../../css/b/bsm7zc0tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a-wkamaxf"/><path class="bsm7zc0tv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:prowlarr-radarr" {...props}></Icon>

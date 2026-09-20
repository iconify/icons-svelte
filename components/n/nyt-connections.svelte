<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzopzya5k.css';
import '../../css/z/zi8fv1mfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hzopzya5k"/><path class="zi8fv1mfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nyt-connections" {...props}></Icon>

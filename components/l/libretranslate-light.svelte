<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlcn24b2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vlcn24b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:libretranslate-light" {...props}></Icon>

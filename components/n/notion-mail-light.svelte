<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx29zvbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fx29zvbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:notion-mail-light" {...props}></Icon>

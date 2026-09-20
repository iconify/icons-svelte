<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be4ocjgyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="be4ocjgyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:emote-happy" {...props}></Icon>

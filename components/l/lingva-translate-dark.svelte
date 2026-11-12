<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlxh2kfbr.css';
import '../../css/x/xsuq0vbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hlxh2kfbr"/><path class="xsuq0vbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lingva-translate-dark" {...props}></Icon>

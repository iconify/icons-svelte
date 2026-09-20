<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otn30pbbb.css';
import '../../css/b/bezz-3_ya.css';
import '../../css/v/v-xbbnb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="otn30pbbb"/><path class="bezz-3_ya"/><path class="v-xbbnb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:little-chat" {...props}></Icon>

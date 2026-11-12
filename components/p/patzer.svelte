<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlrdzybyn.css';
import '../../css/y/yjo15eh2h.css';
import '../../css/z/z5-xgab6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hlrdzybyn"/><path class="yjo15eh2h"/><path class="z5-xgab6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:patzer" {...props}></Icon>

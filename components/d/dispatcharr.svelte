<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdaxkdb1q.css';
import '../../css/l/l-nhlab9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rdaxkdb1q"/><path class="l-nhlab9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dispatcharr" {...props}></Icon>

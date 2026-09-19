<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0eeupfys.css';
import '../../css/w/ws8a0lt4p.css';
import '../../css/s/sr-_ec-wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u0eeupfys"/><path class="ws8a0lt4p"/><path class="sr-_ec-wh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:document-attach-outline" {...props}></Icon>

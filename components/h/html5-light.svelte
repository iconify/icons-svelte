<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smn7yqb_q.css';
import '../../css/e/eyfgxacfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="smn7yqb_q"/><path class="eyfgxacfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:html5-light" {...props}></Icon>

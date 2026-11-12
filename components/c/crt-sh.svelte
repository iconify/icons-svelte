<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa-vdingl.css';
import '../../css/s/sr532hb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qa-vdingl"/><path class="sr532hb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crt-sh" {...props}></Icon>

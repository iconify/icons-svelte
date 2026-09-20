<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3ft7sbvr.css';
import '../../css/p/p-jt3neah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h3ft7sbvr"/><path class="p-jt3neah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:haus" {...props}></Icon>

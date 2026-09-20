<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm84comle.css';
import '../../css/l/l2q_0xbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pm84comle"/><path class="l2q_0xbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adobe-acrobat" {...props}></Icon>

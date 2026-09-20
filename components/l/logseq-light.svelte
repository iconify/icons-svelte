<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtmtpb1fz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wtmtpb1fz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:logseq-light" {...props}></Icon>

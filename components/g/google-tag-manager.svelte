<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6ue2-jip.css';
import '../../css/y/yy45p2b8q.css';
import '../../css/z/z271pgbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e6ue2-jip"/><path class="yy45p2b8q"/><circle class="z271pgbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-tag-manager" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk_xv4fcw.css';
import '../../css/i/iyf1u4g7c.css';
import '../../css/a/aspzlbb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mk_xv4fcw"/><path class="iyf1u4g7c"/><path class="aspzlbb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:glance" {...props}></Icon>

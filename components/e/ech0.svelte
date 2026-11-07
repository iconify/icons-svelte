<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6iw_7bgc.css';
import '../../css/t/t2qw1ybvw.css';
import '../../css/o/o394wrbot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="u6iw_7bgc"/><circle class="t2qw1ybvw"/><path class="o394wrbot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ech0" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1hpn4bjj.css';
import '../../css/w/w_0godbis.css';
import '../../css/a/asyhpobbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o1hpn4bjj"/><path class="w_0godbis"/><path class="asyhpobbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:fiscal-host-16" {...props}></Icon>

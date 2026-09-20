<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhyxh_bqu.css';
import '../../css/g/gcf5i_czd.css';
import '../../css/g/gq800qhcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fhyxh_bqu"/><path class="gcf5i_czd"/><path class="gq800qhcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-stop-sign-2" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur-d651vm.css';
import '../../css/n/nzbz80bhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ur-d651vm"/><path class="nzbz80bhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:monero" {...props}></Icon>

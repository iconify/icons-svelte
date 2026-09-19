<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjonbacvn.css';
import '../../css/c/cfprd2egi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vjonbacvn"/><path class="cfprd2egi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:information-sharp" {...props}></Icon>

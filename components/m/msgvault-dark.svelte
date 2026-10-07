<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp2n0tx7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mp2n0tx7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:msgvault-dark" {...props}></Icon>

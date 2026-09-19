<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo8ap71oo.css';
import '../../css/o/ooj3jip1b.css';
import '../../css/f/fhqdiozkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo8ap71oo"/><circle class="ooj3jip1b"/><circle class="fhqdiozkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:premium-network-tier" {...props}></Icon>

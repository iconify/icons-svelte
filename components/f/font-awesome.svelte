<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrv2rcjel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="nrv2rcjel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:font-awesome" {...props}></Icon>

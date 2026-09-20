<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m40w_1l6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m40w_1l6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crowdsec-manager-light" {...props}></Icon>

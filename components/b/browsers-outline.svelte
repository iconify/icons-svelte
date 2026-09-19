<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpbqltkex.css';
import '../../css/m/mkt8b3bpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="wpbqltkex"/><path class="mkt8b3bpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:browsers-outline" {...props}></Icon>

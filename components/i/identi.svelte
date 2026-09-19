<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5fehibxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":480};
const content = `<path class="m5fehibxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:identi" {...props}></Icon>

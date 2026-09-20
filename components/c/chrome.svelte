<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq999kwzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="iq999kwzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:chrome" {...props}></Icon>

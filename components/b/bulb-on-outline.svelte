<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj1g08qrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sj1g08qrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bulb-on-outline" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsomq0bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="vsomq0bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:forward-circle-solid" {...props}></Icon>

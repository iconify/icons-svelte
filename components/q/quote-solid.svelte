<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0f9s_bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k0f9s_bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:quote-solid" {...props}></Icon>

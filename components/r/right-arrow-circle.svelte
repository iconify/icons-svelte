<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr8u2x3pd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mr8u2x3pd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:right-arrow-circle" {...props}></Icon>

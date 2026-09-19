<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isyw8ybmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="isyw8ybmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:designfloat" {...props}></Icon>

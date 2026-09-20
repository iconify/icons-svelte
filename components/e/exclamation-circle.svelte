<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbtulp5np.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lbtulp5np"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:exclamation-circle" {...props}></Icon>

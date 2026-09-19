<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfi_23bhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kfi_23bhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-up-a" {...props}></Icon>

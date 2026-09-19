<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivhs00kbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ivhs00kbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:react" {...props}></Icon>

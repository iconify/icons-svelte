<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klg9wvjas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="klg9wvjas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:moon-cloud" {...props}></Icon>

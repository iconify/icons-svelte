<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovix37yeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ovix37yeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:government-14" {...props}></Icon>

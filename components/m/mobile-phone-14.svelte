<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkwb1-b2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="tkwb1-b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:mobile-phone-14" {...props}></Icon>

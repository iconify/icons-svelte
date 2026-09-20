<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgh789bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="tgh789bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:hifi-14" {...props}></Icon>

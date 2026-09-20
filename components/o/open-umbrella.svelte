<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcr02fcny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mcr02fcny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:open-umbrella" {...props}></Icon>

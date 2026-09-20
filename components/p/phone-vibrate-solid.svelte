<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpv54j2pr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mpv54j2pr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:phone-vibrate-solid" {...props}></Icon>

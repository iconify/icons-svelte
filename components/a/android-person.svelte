<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhbybdlve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vhbybdlve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-person" {...props}></Icon>

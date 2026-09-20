<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kremzy3_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kremzy3_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:android-police-dark" {...props}></Icon>

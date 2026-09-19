<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icacskyay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="icacskyay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:play-forward-circle-sharp" {...props}></Icon>

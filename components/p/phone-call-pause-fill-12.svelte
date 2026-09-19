<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imgn3pbml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="imgn3pbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-call-pause-fill-12" {...props}></Icon>

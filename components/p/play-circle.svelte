<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwcmttnff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iwcmttnff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:play-circle" {...props}></Icon>

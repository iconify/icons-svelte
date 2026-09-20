<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl1kp80tz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hl1kp80tz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:onyx-light" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz5qhoa4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tz5qhoa4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:authentik-light" {...props}></Icon>

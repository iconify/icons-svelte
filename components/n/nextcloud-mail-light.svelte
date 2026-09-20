<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy6gxbbso.css';
import '../../css/h/hdoub2b9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vy6gxbbso"/><path class="hdoub2b9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-mail-light" {...props}></Icon>

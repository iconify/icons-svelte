<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md81p0dal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="md81p0dal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linuxgsm-light" {...props}></Icon>

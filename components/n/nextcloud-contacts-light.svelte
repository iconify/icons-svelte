<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6d9_xu_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i6d9_xu_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-contacts-light" {...props}></Icon>

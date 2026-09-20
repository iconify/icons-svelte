<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyt432bcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hyt432bcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-notes-light" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptx1sh0xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ptx1sh0xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-calendar-dark" {...props}></Icon>

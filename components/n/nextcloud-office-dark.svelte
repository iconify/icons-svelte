<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc6fdccls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pc6fdccls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-office-dark" {...props}></Icon>

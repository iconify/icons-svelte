<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wja-47b6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wja-47b6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:edubuntu-dark" {...props}></Icon>

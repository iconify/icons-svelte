<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_105xiqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h_105xiqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:owncloud" {...props}></Icon>

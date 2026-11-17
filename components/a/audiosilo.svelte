<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_7eslrjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p_7eslrjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:audiosilo" {...props}></Icon>

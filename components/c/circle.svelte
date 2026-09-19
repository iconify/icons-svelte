<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo3r6sbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="yo3r6sbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:circle" {...props}></Icon>

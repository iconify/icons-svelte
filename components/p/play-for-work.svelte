<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0ui89byk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":384};
const content = `<path class="z0ui89byk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:play-for-work" {...props}></Icon>

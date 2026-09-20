<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjqfp0b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jjqfp0b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kan-dark" {...props}></Icon>

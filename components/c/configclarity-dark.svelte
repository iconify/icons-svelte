<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkyc7bbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pkyc7bbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:configclarity-dark" {...props}></Icon>

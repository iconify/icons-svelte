<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/demyu2alk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="demyu2alk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:akaunting-light" {...props}></Icon>

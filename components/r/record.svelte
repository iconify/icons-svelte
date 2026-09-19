<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt9eu9bze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bt9eu9bze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:record" {...props}></Icon>

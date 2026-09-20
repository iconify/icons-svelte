<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghek0nbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ghek0nbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nginx-light" {...props}></Icon>

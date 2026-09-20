<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alpcz-bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="alpcz-bwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:notion-calendar-dark" {...props}></Icon>

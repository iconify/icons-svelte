<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl_f9mdkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xl_f9mdkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:arrow-alt-circle-right" {...props}></Icon>

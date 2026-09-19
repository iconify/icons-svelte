<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikr30cc0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="ikr30cc0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:flushed" {...props}></Icon>

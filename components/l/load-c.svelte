<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8lhuhb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s8lhuhb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:load-c" {...props}></Icon>

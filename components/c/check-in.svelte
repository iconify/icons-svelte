<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7rob5hgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d7rob5hgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:check-in" {...props}></Icon>

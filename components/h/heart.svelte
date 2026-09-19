<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3s4zvj1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":663};
const content = `<path class="v3s4zvj1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:heart" {...props}></Icon>

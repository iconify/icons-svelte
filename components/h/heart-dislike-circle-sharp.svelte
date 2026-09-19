<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6q1ptbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v6q1ptbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:heart-dislike-circle-sharp" {...props}></Icon>

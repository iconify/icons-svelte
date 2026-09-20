<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j68bju_gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j68bju_gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:loandash-light" {...props}></Icon>

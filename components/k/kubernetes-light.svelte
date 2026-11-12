<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_eb1s5-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s_eb1s5-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kubernetes-light" {...props}></Icon>

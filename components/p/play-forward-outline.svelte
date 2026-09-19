<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_1zkkb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p_1zkkb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:play-forward-outline" {...props}></Icon>

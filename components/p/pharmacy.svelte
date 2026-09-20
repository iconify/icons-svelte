<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5_g_9b5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="g5_g_9b5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:pharmacy" {...props}></Icon>

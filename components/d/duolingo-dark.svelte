<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioj85kbhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ioj85kbhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:duolingo-dark" {...props}></Icon>

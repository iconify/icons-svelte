<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk-ljkbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":650,"height":679};
const content = `<path class="nk-ljkbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:calendar" {...props}></Icon>

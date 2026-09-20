<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4fzszs3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v4fzszs3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kometa-light" {...props}></Icon>

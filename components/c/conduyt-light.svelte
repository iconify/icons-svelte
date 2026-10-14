<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf0dqmblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hf0dqmblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:conduyt-light" {...props}></Icon>

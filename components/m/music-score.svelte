<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edhpo_owh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="edhpo_owh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:music-score" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w02q53zfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="w02q53zfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:folder" {...props}></Icon>

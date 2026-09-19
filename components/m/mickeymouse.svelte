<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s730z_fif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":960};
const content = `<path class="s730z_fif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:mickeymouse" {...props}></Icon>

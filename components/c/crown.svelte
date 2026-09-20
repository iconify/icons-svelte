<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue8808q3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue8808q3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:crown" {...props}></Icon>

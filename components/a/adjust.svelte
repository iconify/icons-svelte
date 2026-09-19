<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np8z34b5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="np8z34b5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:adjust" {...props}></Icon>

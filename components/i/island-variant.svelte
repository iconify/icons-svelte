<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_svf083s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_svf083s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:island-variant" {...props}></Icon>

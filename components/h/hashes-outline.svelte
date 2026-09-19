<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvx0o4p_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvx0o4p_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:hashes-outline" {...props}></Icon>

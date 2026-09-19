<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izli1gr-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izli1gr-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:binary" {...props}></Icon>

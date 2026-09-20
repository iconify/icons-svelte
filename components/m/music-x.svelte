<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tygr07bdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tygr07bdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:music-x" {...props}></Icon>

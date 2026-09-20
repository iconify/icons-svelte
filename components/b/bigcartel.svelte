<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_wig27sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_wig27sw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:bigcartel" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st7sd8ykf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st7sd8ykf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:moon-bold" {...props}></Icon>

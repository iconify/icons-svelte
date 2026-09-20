<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5y010g_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5y010g_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-to-top-right-linear" {...props}></Icon>

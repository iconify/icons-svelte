<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibg-916rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibg-916rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:border-left-01" {...props}></Icon>

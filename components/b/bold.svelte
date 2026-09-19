<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um75jabhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um75jabhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bold" {...props}></Icon>

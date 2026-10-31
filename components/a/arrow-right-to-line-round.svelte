<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um5f_xfat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um5f_xfat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-right-to-line-round" {...props}></Icon>

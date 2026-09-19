<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtdd95ihe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtdd95ihe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:gift-outline" {...props}></Icon>

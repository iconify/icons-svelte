<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3df2w8cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f3df2w8cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-ribbons-star-outline" {...props}></Icon>

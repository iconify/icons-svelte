<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdaq20_bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdaq20_bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:link-share-2" {...props}></Icon>

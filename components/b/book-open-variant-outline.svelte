<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytvefubef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytvefubef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-open-variant-outline" {...props}></Icon>

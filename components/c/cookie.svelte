<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mub4lvbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mub4lvbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cookie" {...props}></Icon>

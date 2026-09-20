<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb1748b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb1748b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:biscuit-remove-outline" {...props}></Icon>

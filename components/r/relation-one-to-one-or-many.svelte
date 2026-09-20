<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxjlo2bty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxjlo2bty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relation-one-to-one-or-many" {...props}></Icon>

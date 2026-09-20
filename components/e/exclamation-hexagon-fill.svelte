<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h80ps7bwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h80ps7bwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:exclamation-hexagon-fill" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbfkku5pk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbfkku5pk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:floor-2" {...props}></Icon>

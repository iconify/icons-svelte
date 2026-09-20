<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ral2q35-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ral2q35-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:add-box" {...props}></Icon>

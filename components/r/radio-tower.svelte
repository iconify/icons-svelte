<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsruq6fcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsruq6fcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:radio-tower" {...props}></Icon>

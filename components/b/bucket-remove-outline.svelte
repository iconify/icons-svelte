<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuwdo0nnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vuwdo0nnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bucket-remove-outline" {...props}></Icon>

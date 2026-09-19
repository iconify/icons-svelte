<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w92u9iv-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w92u9iv-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:attention-square-fill" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixtg6lbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ixtg6lbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cursor-fill" {...props}></Icon>

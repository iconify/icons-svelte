<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idfk1caxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idfk1caxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:dwm" {...props}></Icon>

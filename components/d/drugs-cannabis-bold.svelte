<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us2i0vbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us2i0vbzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:drugs-cannabis-bold" {...props}></Icon>

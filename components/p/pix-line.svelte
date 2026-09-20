<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6tiznvlr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6tiznvlr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pix-line" {...props}></Icon>

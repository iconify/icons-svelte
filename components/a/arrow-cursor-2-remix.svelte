<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzbu5zxuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kzbu5zxuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:arrow-cursor-2-remix" {...props}></Icon>

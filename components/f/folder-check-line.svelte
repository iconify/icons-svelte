<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbkbzvgbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbkbzvgbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-check-line" {...props}></Icon>

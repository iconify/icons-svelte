<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-kqkwbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-kqkwbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fridge-fill" {...props}></Icon>

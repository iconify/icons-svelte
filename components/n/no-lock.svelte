<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9nnki7uc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9nnki7uc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:no-lock" {...props}></Icon>

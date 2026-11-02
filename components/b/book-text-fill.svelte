<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f09ud6upv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f09ud6upv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-text-fill" {...props}></Icon>

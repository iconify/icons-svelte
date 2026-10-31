<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5ugnkbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5ugnkbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:honor" {...props}></Icon>

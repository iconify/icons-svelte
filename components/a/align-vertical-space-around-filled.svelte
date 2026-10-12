<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4e183byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4e183byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:align-vertical-space-around-filled" {...props}></Icon>

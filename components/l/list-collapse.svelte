<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqvgq0beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqvgq0beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:list-collapse" {...props}></Icon>

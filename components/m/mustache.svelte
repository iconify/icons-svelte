<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yie0qniiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yie0qniiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:mustache" {...props}></Icon>

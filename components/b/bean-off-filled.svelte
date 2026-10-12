<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w35knlh6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w35knlh6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bean-off-filled" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-4t_9btf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-4t_9btf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mango-filled" {...props}></Icon>

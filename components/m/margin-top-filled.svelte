<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-o92wb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-o92wb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:margin-top-filled" {...props}></Icon>

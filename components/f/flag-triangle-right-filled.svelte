<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo5g7ob-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo5g7ob-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:flag-triangle-right-filled" {...props}></Icon>

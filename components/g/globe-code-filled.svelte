<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzzmtyb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzzmtyb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:globe-code-filled" {...props}></Icon>

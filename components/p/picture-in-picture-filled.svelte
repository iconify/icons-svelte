<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtubvubud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtubvubud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:picture-in-picture-filled" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq6x7zbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aq6x7zbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:origami-filled" {...props}></Icon>

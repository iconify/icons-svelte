<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa0f-6aya.css';
import '../../css/l/l6ma61byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sa0f-6aya"/><path clip-rule="evenodd" class="l6ma61byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hourglass-cog-filled" {...props}></Icon>

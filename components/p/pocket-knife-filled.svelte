<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py0upebda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="py0upebda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pocket-knife-filled" {...props}></Icon>

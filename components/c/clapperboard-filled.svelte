<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h43-oobqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h43-oobqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:clapperboard-filled" {...props}></Icon>

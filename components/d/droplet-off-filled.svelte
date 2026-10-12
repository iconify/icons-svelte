<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-82q3kkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-82q3kkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:droplet-off-filled" {...props}></Icon>

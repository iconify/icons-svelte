<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi5-0wb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qi5-0wb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-dot-filled" {...props}></Icon>

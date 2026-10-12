<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i32z82ipq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i32z82ipq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:croissant-filled" {...props}></Icon>

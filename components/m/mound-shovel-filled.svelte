<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hens0-_pq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hens0-_pq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mound-shovel-filled" {...props}></Icon>

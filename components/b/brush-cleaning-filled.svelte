<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9uy09baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h9uy09baq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:brush-cleaning-filled" {...props}></Icon>

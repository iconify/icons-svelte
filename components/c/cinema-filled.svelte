<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z317gjqgd.css';
import '../../css/f/ftpvooboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z317gjqgd"/><path clip-rule="evenodd" class="ftpvooboq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cinema-filled" {...props}></Icon>

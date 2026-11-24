<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htbjrccvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htbjrccvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:paint-bucket-filled" {...props}></Icon>

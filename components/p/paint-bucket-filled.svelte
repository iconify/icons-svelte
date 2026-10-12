<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8md41vjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8md41vjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:paint-bucket-filled" {...props}></Icon>

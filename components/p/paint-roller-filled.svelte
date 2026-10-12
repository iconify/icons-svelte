<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv_oh1bhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gv_oh1bhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:paint-roller-filled" {...props}></Icon>

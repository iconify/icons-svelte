<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fopn9jr3y.css';
import '../../css/a/a2_u8gbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fopn9jr3y"/><path class="a2_u8gbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-x-corner-filled" {...props}></Icon>

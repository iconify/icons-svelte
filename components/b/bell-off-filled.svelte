<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0mkieb9c.css';
import '../../css/f/fccyhtt-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0mkieb9c"/><path class="fccyhtt-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bell-off-filled" {...props}></Icon>

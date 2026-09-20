<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa86d2bfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aa86d2bfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:computer-chip-1" {...props}></Icon>

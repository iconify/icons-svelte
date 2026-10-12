<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbo3gpfgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbo3gpfgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:monitor-off-filled" {...props}></Icon>

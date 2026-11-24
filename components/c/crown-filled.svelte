<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb4lz6bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lb4lz6bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:crown-filled" {...props}></Icon>

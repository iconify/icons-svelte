<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn_2kjoxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wn_2kjoxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:candy-filled" {...props}></Icon>

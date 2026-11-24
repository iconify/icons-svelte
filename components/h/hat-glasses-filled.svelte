<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwavrg0fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwavrg0fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hat-glasses-filled" {...props}></Icon>

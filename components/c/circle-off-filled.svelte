<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gts7rybfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gts7rybfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-off-filled" {...props}></Icon>

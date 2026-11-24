<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4czd-yco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4czd-yco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:candy-cane-filled" {...props}></Icon>

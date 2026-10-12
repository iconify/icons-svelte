<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j95p8463r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j95p8463r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:eye-dashed-filled" {...props}></Icon>

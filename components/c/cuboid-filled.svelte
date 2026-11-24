<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6b17ub6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6b17ub6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cuboid-filled" {...props}></Icon>

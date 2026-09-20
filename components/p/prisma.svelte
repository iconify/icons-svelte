<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx3tqmbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx3tqmbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:prisma" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9o3_3bkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9o3_3bkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-left" {...props}></Icon>

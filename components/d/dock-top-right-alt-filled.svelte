<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g01q5um2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g01q5um2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-top-right-alt-filled" {...props}></Icon>

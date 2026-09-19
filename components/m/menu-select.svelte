<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m32k1ef5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m32k1ef5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:menu-select" {...props}></Icon>

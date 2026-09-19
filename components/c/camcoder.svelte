<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0-h4wb-b.css';
import '../../css/o/ordrlvixz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0-h4wb-b"/><path class="ordrlvixz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:camcoder" {...props}></Icon>

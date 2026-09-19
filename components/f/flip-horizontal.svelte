<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjfkx4bvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjfkx4bvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:flip-horizontal" {...props}></Icon>

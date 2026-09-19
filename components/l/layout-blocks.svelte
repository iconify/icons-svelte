<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft97n1bfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft97n1bfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:layout-blocks" {...props}></Icon>

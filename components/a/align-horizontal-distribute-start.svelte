<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbuufs0zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbuufs0zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:align-horizontal-distribute-start" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e594ecccl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e594ecccl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:acorn" {...props}></Icon>

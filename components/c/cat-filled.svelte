<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq6wx1c7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uq6wx1c7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cat-filled" {...props}></Icon>

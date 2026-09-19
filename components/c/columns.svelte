<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgx5tmbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":29,"height":24};
const content = `<path class="zgx5tmbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:columns" {...props}></Icon>

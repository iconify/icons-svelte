<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uduaotbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uduaotbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrows-move" {...props}></Icon>

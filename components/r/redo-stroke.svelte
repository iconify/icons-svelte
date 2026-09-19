<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj9e8cckx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cj9e8cckx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:redo-stroke" {...props}></Icon>

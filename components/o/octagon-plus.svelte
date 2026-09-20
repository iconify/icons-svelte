<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn9vxj7ii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qn9vxj7ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:octagon-plus" {...props}></Icon>

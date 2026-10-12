<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb5l8-b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pb5l8-b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:pipeline-plus" {...props}></Icon>

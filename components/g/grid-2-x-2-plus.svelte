<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-myih1aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-myih1aj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:grid-2-x-2-plus" {...props}></Icon>

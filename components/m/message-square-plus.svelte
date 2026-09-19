<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-29rqb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-29rqb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-square-plus" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdqo3k3dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdqo3k3dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:piano-grand-filled" {...props}></Icon>

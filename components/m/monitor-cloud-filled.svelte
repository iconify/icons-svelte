<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgqe2rbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cgqe2rbxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:monitor-cloud-filled" {...props}></Icon>

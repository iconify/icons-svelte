<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhm6svbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nhm6svbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:columns-3-fill" {...props}></Icon>

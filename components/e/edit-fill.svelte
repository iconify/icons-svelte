<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epnyl-bbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epnyl-bbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:edit-fill" {...props}></Icon>

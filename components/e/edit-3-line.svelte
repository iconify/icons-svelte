<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-pk5x7ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-pk5x7ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:edit-3-line" {...props}></Icon>

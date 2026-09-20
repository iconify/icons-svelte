<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xisg-gb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xisg-gb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-right-circle-fill" {...props}></Icon>

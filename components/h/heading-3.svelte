<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk90pdnnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tk90pdnnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:heading-3" {...props}></Icon>

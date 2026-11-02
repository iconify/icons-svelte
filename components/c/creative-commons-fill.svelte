<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1884bqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc1884bqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:creative-commons-fill" {...props}></Icon>

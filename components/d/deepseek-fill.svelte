<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as8ev18tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="as8ev18tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:deepseek-fill" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7v983b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7v983b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-compare-line" {...props}></Icon>

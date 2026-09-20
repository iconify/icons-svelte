<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2d9zgb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2d9zgb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:anchor-fill" {...props}></Icon>

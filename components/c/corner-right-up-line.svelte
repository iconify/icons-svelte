<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5px82j8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5px82j8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:corner-right-up-line" {...props}></Icon>

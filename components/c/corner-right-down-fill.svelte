<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-xh4q-md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-xh4q-md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:corner-right-down-fill" {...props}></Icon>

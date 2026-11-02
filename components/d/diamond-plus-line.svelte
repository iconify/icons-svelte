<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_8v1sbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_8v1sbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:diamond-plus-line" {...props}></Icon>

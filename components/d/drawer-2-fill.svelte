<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab5x98fnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ab5x98fnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drawer-2-fill" {...props}></Icon>

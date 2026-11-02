<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y79gy02xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y79gy02xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bone-fill" {...props}></Icon>

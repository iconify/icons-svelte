<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1awk1bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1awk1bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:add-light" {...props}></Icon>

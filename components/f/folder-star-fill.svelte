<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owoww--fz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owoww--fz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-star-fill" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3kpvpa4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3kpvpa4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:image-down-fill" {...props}></Icon>

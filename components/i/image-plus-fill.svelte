<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izim1lb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izim1lb0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:image-plus-fill" {...props}></Icon>

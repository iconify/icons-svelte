<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b46jhob4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b46jhob4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:picture-in-picture-fill-round" {...props}></Icon>

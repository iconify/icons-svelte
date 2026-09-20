<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfeqwxbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfeqwxbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:image-ai-line" {...props}></Icon>

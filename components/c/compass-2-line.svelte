<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8ykcmbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8ykcmbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:compass-2-line" {...props}></Icon>

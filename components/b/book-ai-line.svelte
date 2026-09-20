<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4mk-iblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4mk-iblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:book-ai-line" {...props}></Icon>

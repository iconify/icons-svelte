<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zshp-2y7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zshp-2y7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-lock-fill" {...props}></Icon>

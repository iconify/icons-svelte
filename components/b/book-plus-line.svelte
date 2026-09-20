<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo149e-4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo149e-4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:book-plus-line" {...props}></Icon>

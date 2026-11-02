<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7xhyxb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7xhyxb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-open-text-fill" {...props}></Icon>

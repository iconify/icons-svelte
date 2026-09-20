<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xejf3lboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xejf3lboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:book-line" {...props}></Icon>

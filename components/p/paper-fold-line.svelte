<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yty-xqb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yty-xqb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:paper-fold-line" {...props}></Icon>

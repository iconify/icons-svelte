<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx1v9mbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zx1v9mbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:book-plus" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be91xibpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="be91xibpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:article-line" {...props}></Icon>

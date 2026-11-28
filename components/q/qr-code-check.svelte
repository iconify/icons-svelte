<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc8wbgb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zc8wbgb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:qr-code-check" {...props}></Icon>

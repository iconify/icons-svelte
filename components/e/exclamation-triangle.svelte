<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikia-1bis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikia-1bis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:exclamation-triangle" {...props}></Icon>

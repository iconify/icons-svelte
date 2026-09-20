<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd57n2brx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bd57n2brx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-nigeria-fill" {...props}></Icon>

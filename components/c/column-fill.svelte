<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h26g72gzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h26g72gzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:column-fill" {...props}></Icon>

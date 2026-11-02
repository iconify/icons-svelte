<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqn0q7xpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqn0q7xpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-key-line" {...props}></Icon>

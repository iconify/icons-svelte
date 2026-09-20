<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n53gf5b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n53gf5b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cursor-line" {...props}></Icon>

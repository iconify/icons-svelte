<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfh15160c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfh15160c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:case-upper-fill" {...props}></Icon>

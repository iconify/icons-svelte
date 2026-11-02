<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brc5an_7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brc5an_7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:left-small-line" {...props}></Icon>

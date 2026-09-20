<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8mvo4c9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8mvo4c9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gift-line" {...props}></Icon>

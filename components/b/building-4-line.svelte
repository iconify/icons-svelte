<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5o7mcc7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5o7mcc7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:building-4-line" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b475p4q9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b475p4q9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:building-5-line" {...props}></Icon>

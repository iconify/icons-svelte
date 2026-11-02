<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsu2-fabk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsu2-fabk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:campfire-fill" {...props}></Icon>

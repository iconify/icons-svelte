<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhwr5ohqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhwr5ohqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hop-2-off-fill" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkyq4gbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xkyq4gbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bus-line" {...props}></Icon>

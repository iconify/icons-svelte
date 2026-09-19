<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3-t_9bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="d3-t_9bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-crop-square" {...props}></Icon>

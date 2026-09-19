<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s68c4_3ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="s68c4_3ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:drop-triangle-fill" {...props}></Icon>

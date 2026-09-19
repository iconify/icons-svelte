<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmh5s_g6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="tmh5s_g6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:option" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_o7fzbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="t_o7fzbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:call" {...props}></Icon>

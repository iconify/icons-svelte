<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_bf30izc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":643,"height":696};
const content = `<path class="v_bf30izc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:bold" {...props}></Icon>

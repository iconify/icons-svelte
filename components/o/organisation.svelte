<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy8t_d1rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="jy8t_d1rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:organisation" {...props}></Icon>

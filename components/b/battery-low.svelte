<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jswgxzn3t.css';
import '../../css/u/u5z_1ibwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jswgxzn3t"/><path class="u5z_1ibwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:battery-low" {...props}></Icon>

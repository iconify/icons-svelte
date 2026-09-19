<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jswgxzn3t.css';
import '../../css/l/lfxgm_3mg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jswgxzn3t"/><path class="lfxgm_3mg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:battery-1" {...props}></Icon>

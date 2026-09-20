<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jff5k-bht.css';
import '../../css/t/tpx4xacpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jff5k-bht"/><path class="tpx4xacpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:pivot-column-24" {...props}></Icon>

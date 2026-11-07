<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm03gzbnp.css';
import '../../css/k/kd97c6bdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path class="kd97c6bdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:graph-bold-duotone" {...props}></Icon>

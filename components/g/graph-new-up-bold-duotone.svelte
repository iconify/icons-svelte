<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm03gzbnp.css';
import '../../css/q/q-ty8vbuh.css';
import '../../css/y/yp5dl9p5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path class="q-ty8vbuh"/><path class="yp5dl9p5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:graph-new-up-bold-duotone" {...props}></Icon>

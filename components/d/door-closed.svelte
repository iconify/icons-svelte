<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rszqa-p5t.css';
import '../../css/n/n8-3fdb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rszqa-p5t"/><path class="n8-3fdb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:door-closed" {...props}></Icon>

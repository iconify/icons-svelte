<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/robrqs70q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="robrqs70q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:prezi" {...props}></Icon>

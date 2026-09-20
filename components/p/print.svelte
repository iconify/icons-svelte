<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep9p_6bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ep9p_6bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:print" {...props}></Icon>

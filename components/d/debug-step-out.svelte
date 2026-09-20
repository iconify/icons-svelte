<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcbzydbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcbzydbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:debug-step-out" {...props}></Icon>

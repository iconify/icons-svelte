<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5m-_tbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5m-_tbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:puzzle-line" {...props}></Icon>

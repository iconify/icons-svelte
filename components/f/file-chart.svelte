<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjuimz9ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjuimz9ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-chart" {...props}></Icon>

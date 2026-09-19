<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h68a5vtzz.css';
import '../../css/u/u6i9ewq7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="h68a5vtzz"/><path class="u6i9ewq7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:notification" {...props}></Icon>

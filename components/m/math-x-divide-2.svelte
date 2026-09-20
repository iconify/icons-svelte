<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1bdebg5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1bdebg5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:math-x-divide-2" {...props}></Icon>

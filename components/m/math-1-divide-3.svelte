<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hklz5bu9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hklz5bu9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:math-1-divide-3" {...props}></Icon>

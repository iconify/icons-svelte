<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7ahtgoqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7ahtgoqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:math-x-divide-y-2" {...props}></Icon>

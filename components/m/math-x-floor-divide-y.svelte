<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8pigpexp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8pigpexp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:math-x-floor-divide-y" {...props}></Icon>

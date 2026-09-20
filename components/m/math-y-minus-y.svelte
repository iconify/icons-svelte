<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i84mfemjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i84mfemjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:math-y-minus-y" {...props}></Icon>

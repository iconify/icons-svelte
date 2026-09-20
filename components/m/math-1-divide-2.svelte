<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4gxffbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4gxffbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:math-1-divide-2" {...props}></Icon>

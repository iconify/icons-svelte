<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_w2fmb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_w2fmb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flag-key" {...props}></Icon>

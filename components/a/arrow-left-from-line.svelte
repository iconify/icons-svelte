<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0tlg44yp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0tlg44yp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-left-from-line" {...props}></Icon>

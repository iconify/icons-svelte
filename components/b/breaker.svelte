<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_rm4k30i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_rm4k30i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:breaker" {...props}></Icon>

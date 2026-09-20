<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp4j1ldlo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="lp4j1ldlo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:line-dotted" {...props}></Icon>

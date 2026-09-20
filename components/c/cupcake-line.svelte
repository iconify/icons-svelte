<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prb5lc1je.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prb5lc1je"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cupcake-line" {...props}></Icon>

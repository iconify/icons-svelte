<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-06obvoh.css';
import '../../css/c/co-hgrdtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-06obvoh"/><path class="co-hgrdtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fried-egg-line" {...props}></Icon>

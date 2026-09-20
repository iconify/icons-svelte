<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-n99mbgf.css';
import '../../css/a/atk21rbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f-n99mbgf"/><ellipse class="atk21rbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:printer" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brftz6bit.css';
import '../../css/v/vj7j3db8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="brftz6bit"/><path class="vj7j3db8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:laraveljetstream-wordmark" {...props}></Icon>

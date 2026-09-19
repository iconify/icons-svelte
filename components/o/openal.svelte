<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2wr9wc8g.css';
import '../../css/n/nn222kb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="l2wr9wc8g"/><path class="nn222kb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:openal" {...props}></Icon>

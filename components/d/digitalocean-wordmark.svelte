<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al88j65bh.css';
import '../../css/j/jd1srsr7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="al88j65bh"/><path class="jd1srsr7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:digitalocean-wordmark" {...props}></Icon>

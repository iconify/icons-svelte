<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv6_rebxi.css';
import '../../css/a/ak3pdnn1p.css';
import '../../css/s/sv8sqhg9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iv6_rebxi"/><path class="ak3pdnn1p"/><path class="sv8sqhg9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:co2-pipeline-20" {...props}></Icon>

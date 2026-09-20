<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifk2jpbym.css';
import '../../css/d/danpsob9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ifk2jpbym"/><path class="danpsob9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:link" {...props}></Icon>

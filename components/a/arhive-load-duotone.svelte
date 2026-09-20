<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j724_zblf.css';
import '../../css/o/osytbzbjy.css';
import '../../css/r/rycy52bgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j724_zblf"/><path class="osytbzbjy"/><path class="rycy52bgk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:arhive-load-duotone" {...props}></Icon>

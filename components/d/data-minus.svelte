<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/flc7jgumq.css';
import '../../css/m/mc3kzzn3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="flc7jgumq"/><path class="mc3kzzn3x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:data-minus" {...props}></Icon>

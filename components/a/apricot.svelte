<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/h9f8jm2-z.css';
import '../../css/h/hw1b44bxw.css';
import '../../css/d/d9i98uvix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="h9f8jm2-z"/><path class="hw1b44bxw"/><path class="d9i98uvix"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:apricot" {...props}></Icon>

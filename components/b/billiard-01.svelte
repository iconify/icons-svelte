<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/iajx504bs.css';
import '../../css/q/qmvobh65p.css';
import '../../css/d/dj3sakoey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="iajx504bs"/><path class="qmvobh65p"/><path class="dj3sakoey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:billiard-01" {...props}></Icon>

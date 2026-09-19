<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx8y2ds-k.css';
import '../../css/m/mwfiol2dj.css';
import '../../css/r/rwc7d5bjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gx8y2ds-k"><path class="mwfiol2dj"/><path class="rwc7d5bjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:align-left" {...props}></Icon>

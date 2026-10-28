<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/c/c90yv5-jm.css';
import '../../css/n/navkqjbfd.css';
import '../../css/i/i6k0atkeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c90yv5-jm"/><path class="navkqjbfd"/><path class="i6k0atkeb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chart-radar" {...props}></Icon>

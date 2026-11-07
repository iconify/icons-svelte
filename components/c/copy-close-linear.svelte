<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/omhvxckds.css';
import '../../css/v/v0ldy8l7g.css';
import '../../css/k/kmh5_x81g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="omhvxckds"/><path class="v0ldy8l7g"/><path class="kmh5_x81g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:copy-close-linear" {...props}></Icon>

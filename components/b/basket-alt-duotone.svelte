<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/ouo3q_epq.css';
import '../../css/f/fo_f5l8hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ouo3q_epq"/><path class="fo_f5l8hd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:basket-alt-duotone" {...props}></Icon>

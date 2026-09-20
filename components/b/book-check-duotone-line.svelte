<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/voy24ybuj.css';
import '../../css/f/fod7kbbzn.css';
import '../../css/n/nsr8k1bza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="voy24ybuj"/><path class="fod7kbbzn"/><path class="nsr8k1bza"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:book-check-duotone-line" {...props}></Icon>

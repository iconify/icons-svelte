<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wxqvdebjs.css';
import '../../css/g/g-2ubmb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wxqvdebjs"/><path clip-rule="evenodd" class="g-2ubmb5c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:mail-send-envelope-flat" {...props}></Icon>

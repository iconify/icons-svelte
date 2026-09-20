<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sn9pucclr.css';
import '../../css/i/i_gzl-bhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sn9pucclr"/><path clip-rule="evenodd" class="i_gzl-bhv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:contact-book-flat" {...props}></Icon>

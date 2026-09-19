<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/o/o9lb95bos.css';
import '../../css/x/xaw0nda2s.css';
import '../../css/f/fsfedvbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="o9lb95bos"/><path class="xaw0nda2s"/><path class="fsfedvbef"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:lock-off" {...props}></Icon>

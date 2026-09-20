<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub5-3ubuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ub5-3ubuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apache-pdfbox" {...props}></Icon>

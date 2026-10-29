<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-wcl9bei.css';
import '../../css/a/aranxlsbw.css';
import '../../css/o/of4wwqxia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-wcl9bei"/><path class="aranxlsbw"/><path class="of4wwqxia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:barcode" {...props}></Icon>

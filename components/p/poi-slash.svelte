<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7pghdblc.css';
import '../../css/w/wu7dgpbsv.css';
import '../../css/b/b2tobl9de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="l7pghdblc"/><path class="wu7dgpbsv"/><path class="b2tobl9de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:poi-slash" {...props}></Icon>

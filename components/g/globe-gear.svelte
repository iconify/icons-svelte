<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbza77bui.css';
import '../../css/t/tu6holb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="kbza77bui"/><path class="tu6holb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:globe-gear" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br47mpbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="br47mpbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:qgis" {...props}></Icon>

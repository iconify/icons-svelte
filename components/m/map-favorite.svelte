<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8-9vtl6c.css';
import '../../css/n/ng73f_8fh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="c8-9vtl6c"/><path class="ng73f_8fh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-favorite" {...props}></Icon>

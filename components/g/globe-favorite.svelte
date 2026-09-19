<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlp6nh86n.css';
import '../../css/n/ng73f_8fh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="jlp6nh86n"/><path class="ng73f_8fh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:globe-favorite" {...props}></Icon>

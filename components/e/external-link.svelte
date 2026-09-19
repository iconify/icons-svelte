<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_o80v9iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1536};
const content = `<path class="r_o80v9iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:external-link" {...props}></Icon>

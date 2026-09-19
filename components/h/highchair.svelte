<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iot5qp33d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1792};
const content = `<path class="iot5qp33d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:highchair" {...props}></Icon>

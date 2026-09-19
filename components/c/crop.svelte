<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leg09-b4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="leg09-b4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:crop" {...props}></Icon>

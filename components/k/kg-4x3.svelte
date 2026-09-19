<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glbu6gb9k.css';
import '../../css/x/x-vljeb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="glbu6gb9k"/><path class="x-vljeb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:kg-4x3" {...props}></Icon>

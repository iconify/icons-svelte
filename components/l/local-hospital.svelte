<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugua35byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="ugua35byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:local-hospital" {...props}></Icon>

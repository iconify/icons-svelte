<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc8q0j5av.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="tc8q0j5av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:empire" {...props}></Icon>

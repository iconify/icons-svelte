<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsiw1rkpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="tsiw1rkpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:house-chimney-user" {...props}></Icon>

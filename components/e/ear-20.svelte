<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycxe1lb0r.css';
import '../../css/e/eohaobbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ycxe1lb0r"/><path class="eohaobbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ear-20" {...props}></Icon>

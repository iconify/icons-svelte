<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-6jwippj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a-6jwippj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:cloud-download" {...props}></Icon>

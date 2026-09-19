<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbwrjibsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":384};
const content = `<path class="jbwrjibsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:eject-alt" {...props}></Icon>

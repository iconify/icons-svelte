<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjl3xd-zr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qjl3xd-zr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-wearing-greek-cross" {...props}></Icon>

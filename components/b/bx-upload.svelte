<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or20avb8e.css';
import '../../css/u/uotgxeb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or20avb8e"/><path class="uotgxeb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-upload" {...props}></Icon>

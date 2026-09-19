<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-zxp2bdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="h-zxp2bdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:person" {...props}></Icon>

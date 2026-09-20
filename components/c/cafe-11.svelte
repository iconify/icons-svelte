<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt5h8wfck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="qt5h8wfck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:cafe-11" {...props}></Icon>

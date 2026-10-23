<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv6yjefwq.css';
import '../../css/l/lah9vyb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":120,"height":120};
const content = `<rect class="iv6yjefwq"/><path class="lah9vyb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:masheev" {...props}></Icon>

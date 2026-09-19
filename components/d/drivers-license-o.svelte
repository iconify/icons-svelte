<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_0vdbc1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1536};
const content = `<path class="f_0vdbc1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:drivers-license-o" {...props}></Icon>

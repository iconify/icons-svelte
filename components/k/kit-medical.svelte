<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjul6nzne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cjul6nzne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:kit-medical" {...props}></Icon>

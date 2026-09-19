<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/digkmr3fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="digkmr3fv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:file-medical" {...props}></Icon>

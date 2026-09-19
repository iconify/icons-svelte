<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr3a5n0ia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="hr3a5n0ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:earlybirds" {...props}></Icon>

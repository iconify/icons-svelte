<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfn85e6ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jfn85e6ir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:itch-io" {...props}></Icon>

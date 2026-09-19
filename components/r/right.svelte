<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aveyovb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":7,"height":16};
const content = `<path class="aveyovb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:right" {...props}></Icon>

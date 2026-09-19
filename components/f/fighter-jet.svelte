<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz6jcwbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="zz6jcwbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:fighter-jet" {...props}></Icon>

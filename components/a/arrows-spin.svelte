<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvt193c8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="wvt193c8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:arrows-spin" {...props}></Icon>

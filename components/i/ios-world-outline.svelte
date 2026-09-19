<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-8v7zbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x-8v7zbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-world-outline" {...props}></Icon>

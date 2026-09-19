<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agrwl2bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":563,"height":768};
const content = `<path class="agrwl2bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:b" {...props}></Icon>

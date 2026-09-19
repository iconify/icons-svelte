<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9j2k-0au.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="n9j2k-0au"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:pencil-square" {...props}></Icon>

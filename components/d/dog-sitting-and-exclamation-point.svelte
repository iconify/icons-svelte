<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7utfjroc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z7utfjroc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dog-sitting-and-exclamation-point" {...props}></Icon>

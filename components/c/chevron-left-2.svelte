<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-712cbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="z-712cbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chevron-left-2" {...props}></Icon>

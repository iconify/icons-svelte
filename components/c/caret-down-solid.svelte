<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgarisb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lgarisb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:caret-down-solid" {...props}></Icon>

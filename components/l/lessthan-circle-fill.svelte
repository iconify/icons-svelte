<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyx33t-2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="vyx33t-2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:lessthan-circle-fill" {...props}></Icon>

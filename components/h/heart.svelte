<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we63e0kfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="we63e0kfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:heart" {...props}></Icon>

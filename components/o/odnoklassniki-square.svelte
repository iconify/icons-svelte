<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4aoj1bwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i4aoj1bwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:odnoklassniki-square" {...props}></Icon>

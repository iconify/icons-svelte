<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-e96khov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f-e96khov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:angle-down-solid" {...props}></Icon>

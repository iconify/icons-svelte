<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5biw9ofa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u5biw9ofa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:mercury-solid" {...props}></Icon>

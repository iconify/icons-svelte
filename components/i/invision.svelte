<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9vl9objf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s9vl9objf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:invision" {...props}></Icon>

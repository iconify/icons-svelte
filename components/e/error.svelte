<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgt9i3n5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mgt9i3n5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:error" {...props}></Icon>

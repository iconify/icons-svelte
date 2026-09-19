<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcjzqc7he.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":32};
const content = `<path class="bcjzqc7he"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:bargraph" {...props}></Icon>

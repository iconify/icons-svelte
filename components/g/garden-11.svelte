<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9i7bobei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="o9i7bobei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:garden-11" {...props}></Icon>

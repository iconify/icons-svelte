<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7aa6e__k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v7aa6e__k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:globe-americas-fill" {...props}></Icon>

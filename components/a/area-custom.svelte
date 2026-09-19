<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sypmpob3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sypmpob3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:area-custom" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6fj7fx9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z6fj7fx9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:purchasing-organizations" {...props}></Icon>

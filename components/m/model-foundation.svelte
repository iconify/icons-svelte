<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq8qz_u7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zq8qz_u7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:model-foundation" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1zfhk73w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m1zfhk73w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-twitter" {...props}></Icon>

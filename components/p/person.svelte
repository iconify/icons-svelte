<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-7v9o66a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m-7v9o66a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:person" {...props}></Icon>

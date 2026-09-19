<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o59q0tj2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o59q0tj2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:building-electrical" {...props}></Icon>

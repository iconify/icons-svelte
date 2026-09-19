<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyrgegbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nyrgegbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:friendship" {...props}></Icon>

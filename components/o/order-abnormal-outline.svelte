<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3fq8e7_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g3fq8e7_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:order-abnormal-outline" {...props}></Icon>

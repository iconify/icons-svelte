<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onb4l0cqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="onb4l0cqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloud-fog2" {...props}></Icon>

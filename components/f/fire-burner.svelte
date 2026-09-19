<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g87wi1bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="g87wi1bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:fire-burner" {...props}></Icon>

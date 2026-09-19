<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3d5r3obd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s3d5r3obd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:question-diamond-fill" {...props}></Icon>

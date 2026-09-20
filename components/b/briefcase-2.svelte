<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3war6ylu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="s3war6ylu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:briefcase-2" {...props}></Icon>

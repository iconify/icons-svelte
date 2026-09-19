<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqtuzr9cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqtuzr9cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:cloud-arrow-down" {...props}></Icon>

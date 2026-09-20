<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhh9iqynz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhh9iqynz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-j-solid" {...props}></Icon>

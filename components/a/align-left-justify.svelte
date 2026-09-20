<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khitb6bqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khitb6bqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:align-left-justify" {...props}></Icon>

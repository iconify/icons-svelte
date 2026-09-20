<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwmwalbwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwmwalbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-go-forward-line" {...props}></Icon>

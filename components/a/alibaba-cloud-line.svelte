<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3s89bcpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3s89bcpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:alibaba-cloud-line" {...props}></Icon>

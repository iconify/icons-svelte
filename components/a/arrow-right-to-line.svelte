<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alaq-znzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="alaq-znzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-right-to-line" {...props}></Icon>

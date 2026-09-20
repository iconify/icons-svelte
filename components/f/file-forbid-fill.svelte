<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wec3zqpus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wec3zqpus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-forbid-fill" {...props}></Icon>

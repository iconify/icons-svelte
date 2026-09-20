<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8ydtvn7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8ydtvn7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:partly-cloud-night-line" {...props}></Icon>

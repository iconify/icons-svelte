<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6ewh9w8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6ewh9w8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-fading-arrow-up-line" {...props}></Icon>

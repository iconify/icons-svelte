<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3yaeeahm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3yaeeahm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flask-fill" {...props}></Icon>

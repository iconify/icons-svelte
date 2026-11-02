<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wipf8mfog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wipf8mfog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:briefcase-2-line" {...props}></Icon>

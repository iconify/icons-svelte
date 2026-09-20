<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4g2qd-wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4g2qd-wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-download-fill" {...props}></Icon>

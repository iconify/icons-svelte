<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mia6fe8ka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mia6fe8ka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-certificate-fill" {...props}></Icon>

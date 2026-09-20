<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzq729qth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzq729qth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-2-ai-fill" {...props}></Icon>

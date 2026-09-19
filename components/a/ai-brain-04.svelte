<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g93ksbc7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g93ksbc7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-brain-04" {...props}></Icon>

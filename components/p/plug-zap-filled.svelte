<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuwi-34aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kuwi-34aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:plug-zap-filled" {...props}></Icon>

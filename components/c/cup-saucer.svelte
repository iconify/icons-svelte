<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai7oghm0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ai7oghm0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:cup-saucer" {...props}></Icon>

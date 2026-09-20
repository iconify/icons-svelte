<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9veuqatq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9veuqatq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:brain-ai-3-fill" {...props}></Icon>

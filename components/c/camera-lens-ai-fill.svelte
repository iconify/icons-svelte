<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o64tcobbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o64tcobbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:camera-lens-ai-fill" {...props}></Icon>

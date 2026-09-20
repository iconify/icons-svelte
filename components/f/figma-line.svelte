<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo775lb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eo775lb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:figma-line" {...props}></Icon>

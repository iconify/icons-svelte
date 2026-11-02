<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-x-d5bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-x-d5bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bring-to-front-line" {...props}></Icon>

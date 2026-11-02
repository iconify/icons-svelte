<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g04bmkbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g04bmkbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:magic-hat-2-line" {...props}></Icon>

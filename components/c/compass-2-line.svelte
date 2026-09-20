<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0dlm8brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0dlm8brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:compass-2-line" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4fbbbcxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4fbbbcxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-horizontal-center-line" {...props}></Icon>

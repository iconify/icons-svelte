<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kku6257la.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kku6257la"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-square-lock-line" {...props}></Icon>

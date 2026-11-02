<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e96qdrb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e96qdrb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-forward-15-line" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebb0qcc0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebb0qcc0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bottle-glass-line" {...props}></Icon>

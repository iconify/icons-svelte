<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khzxnobue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khzxnobue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hand-two-fingers-line" {...props}></Icon>

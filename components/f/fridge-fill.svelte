<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j385q3ber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j385q3ber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fridge-fill" {...props}></Icon>

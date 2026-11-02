<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4q5kybwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4q5kybwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:decimals-arrow-left-fill" {...props}></Icon>

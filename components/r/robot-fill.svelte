<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwod1ybtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwod1ybtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:robot-fill" {...props}></Icon>

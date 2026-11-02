<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifbk99bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifbk99bir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:keyboard-line" {...props}></Icon>

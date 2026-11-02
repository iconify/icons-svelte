<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox9f654bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox9f654bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:question-2-fill" {...props}></Icon>

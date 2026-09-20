<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euhpbhsyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="euhpbhsyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-history-fill" {...props}></Icon>

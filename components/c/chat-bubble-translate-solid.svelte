<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phew_p5rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="phew_p5rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:chat-bubble-translate-solid" {...props}></Icon>

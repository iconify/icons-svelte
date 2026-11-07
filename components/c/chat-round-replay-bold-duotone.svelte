<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0jc9qlwi.css';
import '../../css/j/j9-jftbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0jc9qlwi"/><path class="j9-jftbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-replay-bold-duotone" {...props}></Icon>

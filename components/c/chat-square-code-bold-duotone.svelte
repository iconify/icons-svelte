<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud6ptt55l.css';
import '../../css/r/r25w052qd.css';
import '../../css/f/frsxhf9nd.css';
import '../../css/g/gchhiqbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ud6ptt55l"/><path class="r25w052qd"/><path class="frsxhf9nd"/><path class="gchhiqbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-code-bold-duotone" {...props}></Icon>

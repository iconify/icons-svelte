<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq367kv2n.css';
import '../../css/q/q9e-uvxvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oq367kv2n"/><path clip-rule="evenodd" class="q9e-uvxvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mailbox-fill" {...props}></Icon>

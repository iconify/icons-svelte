<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-7ackjni.css';
import '../../css/h/h4a5d8u6i.css';
import '../../css/y/y-8n_fb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-7ackjni"/><path class="h4a5d8u6i"/><path clip-rule="evenodd" class="y-8n_fb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pills-bold" {...props}></Icon>

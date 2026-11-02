<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq2r9mbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mq2r9mbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hotkey-fill" {...props}></Icon>

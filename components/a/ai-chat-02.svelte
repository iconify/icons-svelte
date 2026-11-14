<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocs53d2qg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocs53d2qg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-chat-02" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nua2v_4eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nua2v_4eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-new-fill" {...props}></Icon>

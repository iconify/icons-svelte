<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bymgqybfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bymgqybfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-forward-fill" {...props}></Icon>

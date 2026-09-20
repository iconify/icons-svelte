<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejtcomp1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejtcomp1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:chat-text-line" {...props}></Icon>

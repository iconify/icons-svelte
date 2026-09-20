<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae87eiweq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ae87eiweq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:bubble-chat-text-forward" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdhe5xgri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mdhe5xgri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chat-bubble-cancel" {...props}></Icon>

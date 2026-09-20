<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3l21nbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o3l21nbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:help-chat-2-remix" {...props}></Icon>

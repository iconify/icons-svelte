<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdp49sb3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdp49sb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:mailbox" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekqxqyb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekqxqyb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:chat-signal-line" {...props}></Icon>

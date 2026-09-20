<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9l99ntrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9l99ntrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:question-ai-filled" {...props}></Icon>

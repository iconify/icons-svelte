<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv5kxtboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cv5kxtboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mail-ai-line" {...props}></Icon>

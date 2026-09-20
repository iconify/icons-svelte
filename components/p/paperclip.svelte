<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9qwb5mqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="w9qwb5mqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:paperclip" {...props}></Icon>

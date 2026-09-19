<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4oye2aae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e4oye2aae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:emojiangry" {...props}></Icon>

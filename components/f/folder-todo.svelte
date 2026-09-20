<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swsj6o8lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="swsj6o8lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:folder-todo" {...props}></Icon>

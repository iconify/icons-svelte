<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0_j9xhzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="d0_j9xhzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:check-mark" {...props}></Icon>

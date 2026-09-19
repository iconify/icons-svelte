<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejn5f_bfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ejn5f_bfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:hot-dog" {...props}></Icon>

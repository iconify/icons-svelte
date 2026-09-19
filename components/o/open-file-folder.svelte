<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upsw8zbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="upsw8zbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:open-file-folder" {...props}></Icon>

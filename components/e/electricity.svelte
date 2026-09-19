<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7tsvw0-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b7tsvw0-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:electricity" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb1c7ms0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mb1c7ms0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:document-copy" {...props}></Icon>

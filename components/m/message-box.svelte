<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z638kqapw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z638kqapw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:message-box" {...props}></Icon>

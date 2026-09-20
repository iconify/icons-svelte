<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4ril9bys.css';
import '../../css/j/jpg3fab-z.css';
import '../../css/y/y7lv7g-4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e4ril9bys"/><path class="jpg3fab-z"/><path class="y7lv7g-4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:ocr" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f12yfw9qr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f12yfw9qr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:book-with-question-mark" {...props}></Icon>

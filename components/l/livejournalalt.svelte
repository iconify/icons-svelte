<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znggisbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="znggisbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:livejournalalt" {...props}></Icon>

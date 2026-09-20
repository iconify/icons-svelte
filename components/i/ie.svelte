<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f__nc6b9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f__nc6b9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:ie" {...props}></Icon>

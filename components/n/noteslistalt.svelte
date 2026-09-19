<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz5-0vghi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sz5-0vghi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:noteslistalt" {...props}></Icon>

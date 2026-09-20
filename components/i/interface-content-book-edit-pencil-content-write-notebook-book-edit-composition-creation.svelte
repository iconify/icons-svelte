<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br1dpobfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="br1dpobfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-content-book-edit-pencil-content-write-notebook-book-edit-composition-creation" {...props}></Icon>

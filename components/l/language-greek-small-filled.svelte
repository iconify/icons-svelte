<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxo_xnd6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wxo_xnd6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-greek-small-filled" {...props}></Icon>

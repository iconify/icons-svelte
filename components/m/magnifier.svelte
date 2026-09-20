<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me89v47ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="me89v47ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:magnifier" {...props}></Icon>

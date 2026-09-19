<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpjpj5ogm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tpjpj5ogm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:chat-sparkle" {...props}></Icon>

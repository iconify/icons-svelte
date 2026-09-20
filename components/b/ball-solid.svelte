<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwjm1rblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xwjm1rblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ball-solid" {...props}></Icon>

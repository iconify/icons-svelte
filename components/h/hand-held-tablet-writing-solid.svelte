<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab_k1v6wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ab_k1v6wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hand-held-tablet-writing-solid" {...props}></Icon>

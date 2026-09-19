<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi_4cvoay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xi_4cvoay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:rainbow" {...props}></Icon>

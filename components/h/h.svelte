<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-85kbc4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":466,"height":754};
const content = `<path class="t-85kbc4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:h" {...props}></Icon>

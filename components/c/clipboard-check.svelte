<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bulm8yy-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bulm8yy-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:clipboard-check" {...props}></Icon>

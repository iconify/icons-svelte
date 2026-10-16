<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itmoa867s.css';
import '../../css/e/e5jh2b8fa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="itmoa867s"/><path class="e5jh2b8fa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-alert-20" {...props}></Icon>

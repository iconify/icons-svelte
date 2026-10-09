<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is7w60blm.css';
import '../../css/a/axtvywb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="is7w60blm"/><path class="axtvywb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-check-20-bold" {...props}></Icon>

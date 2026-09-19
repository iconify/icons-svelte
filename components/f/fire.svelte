<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqo98j5vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kqo98j5vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:fire" {...props}></Icon>

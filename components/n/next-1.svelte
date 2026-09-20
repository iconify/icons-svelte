<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgsgssc1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qgsgssc1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:next-1" {...props}></Icon>

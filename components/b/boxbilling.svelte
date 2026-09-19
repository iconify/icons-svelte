<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbw8c4bbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qbw8c4bbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:boxbilling" {...props}></Icon>
